<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnqxrgaqv.css';
import '../../css/e/eiyo1ccvq.css';
import '../../css/p/pi8rb54jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnqxrgaqv"/><path class="eiyo1ccvq"/><path class="pi8rb54jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tencentcloud" {...props}></Icon>
