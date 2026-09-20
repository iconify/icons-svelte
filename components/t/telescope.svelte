<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb7520byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kb7520byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:telescope" {...props}></Icon>
