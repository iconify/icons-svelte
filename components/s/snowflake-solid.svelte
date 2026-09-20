<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnv8dyrhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnv8dyrhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:snowflake-solid" {...props}></Icon>
