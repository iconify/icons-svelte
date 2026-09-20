<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj3o6hooc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj3o6hooc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:table-rows-line" {...props}></Icon>
