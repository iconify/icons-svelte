<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usy2kj38d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="usy2kj38d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search2" {...props}></Icon>
