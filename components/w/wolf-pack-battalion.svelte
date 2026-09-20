<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uil06acuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uil06acuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:wolf-pack-battalion" {...props}></Icon>
