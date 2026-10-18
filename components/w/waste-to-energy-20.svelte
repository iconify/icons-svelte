<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yumz50bwm.css';
import '../../css/f/fu_1axbuk.css';
import '../../css/w/wd-cb2baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yumz50bwm"/><path class="fu_1axbuk"/><path class="wd-cb2baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waste-to-energy-20" {...props}></Icon>
