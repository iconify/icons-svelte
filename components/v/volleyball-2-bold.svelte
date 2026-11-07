<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk6whjxer.css';
import '../../css/f/f5wyvtl3b.css';
import '../../css/f/fnd8xqbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk6whjxer"/><path class="f5wyvtl3b"/><path class="fnd8xqbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volleyball-2-bold" {...props}></Icon>
