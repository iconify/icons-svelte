<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga54jte-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ga54jte-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sort-reverse-alphabetically-solid" {...props}></Icon>
