<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e4mii_bgs.css';
import '../../css/m/md286fbip.css';
import '../../css/d/devv6ob4x.css';
import '../../css/f/fo-08g2fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="e4mii_bgs"/><g class="md286fbip"><path class="devv6ob4x"/><path class="fo-08g2fu"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:ryo" {...props}></Icon>
