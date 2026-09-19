<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeulqbctk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="qeulqbctk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:snowflake-4" {...props}></Icon>
