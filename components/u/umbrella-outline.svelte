<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asumzqbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asumzqbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:umbrella-outline" {...props}></Icon>
