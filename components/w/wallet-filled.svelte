<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qre9t1brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qre9t1brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:wallet-filled" {...props}></Icon>
