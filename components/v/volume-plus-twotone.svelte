<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqgjrf.css';
import '../../css/i/iw1iew.css';
import '../../css/c/c-6jkr.css';
import '../../css/y/y4wbml.css';
import '../../css/o/oy7p5c.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-34.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqgjrf iw1iew"/><path class="c-6jkr iw1iew y4wbml"/><path class="iw1iew oy7p5c y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:volume-plus-twotone" {...props}></Icon>
