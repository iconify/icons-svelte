<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6j3bib7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6j3bib7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:ticket-light" {...props}></Icon>
