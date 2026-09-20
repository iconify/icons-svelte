<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/azmqy4_8y.css';
import '../../css/b/bczdprbwo.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVG8B0opepm"><g class="ft5dv1b6b"><path class="azmqy4_8y"/><path class="bczdprbwo"/></g></mask></defs><path mask="url(#SVG8B0opepm)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:ticket-duotone-line" {...props}></Icon>
