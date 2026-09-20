<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zumgnt2vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zumgnt2vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stackshare" {...props}></Icon>
