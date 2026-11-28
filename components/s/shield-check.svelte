<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efocau15t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efocau15t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:shield-check" {...props}></Icon>
