<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/u/ul6gg1m4d.css';
import '../../css/s/sitb2ibko.css';
import '../../css/x/xs42-rkmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ul6gg1m4d"/><path class="sitb2ibko"/><path class="xs42-rkmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:taxi-print" {...props}></Icon>
