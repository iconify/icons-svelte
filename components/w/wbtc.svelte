<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h6z068zxy.css';
import '../../css/m/md286fbip.css';
import '../../css/w/wdu6_l50z.css';
import '../../css/h/h9k36-38v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="h6z068zxy"/><g class="md286fbip"><path class="wdu6_l50z"/><path class="h9k36-38v"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:wbtc" {...props}></Icon>
