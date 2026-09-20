<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5_car.css';
import '../../css/n/n5xegl.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-34.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5_car"/><path class="n5xegl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:star-right-half-twotone" {...props}></Icon>
