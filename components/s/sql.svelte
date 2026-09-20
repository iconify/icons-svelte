<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu8_36bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tu8_36bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sql" {...props}></Icon>
