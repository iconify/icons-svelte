<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eub4bub4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eub4bub4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sun-wind" {...props}></Icon>
