<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i9z6su1jp.css';
import '../../css/u/u1a7mmhai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i9z6su1jp"/><path class="u1a7mmhai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:star-alt-duotone" {...props}></Icon>
