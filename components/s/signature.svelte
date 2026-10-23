<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp4cv6rlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp4cv6rlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:signature" {...props}></Icon>
