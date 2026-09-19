<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pgph-8qhi.css';
import '../../css/m/md286fbip.css';
import '../../css/i/i5r77abpp.css';
import '../../css/s/sbyl84brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="pgph-8qhi"/><g class="md286fbip"><path class="i5r77abpp"/><path class="sbyl84brr"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:uma" {...props}></Icon>
