<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw6_klbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw6_klbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:siren" {...props}></Icon>
