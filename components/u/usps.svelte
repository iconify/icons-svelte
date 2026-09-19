<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzka9l_ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="nzka9l_ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:usps" {...props}></Icon>
