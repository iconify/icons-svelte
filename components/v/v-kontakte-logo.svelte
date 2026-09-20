<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzb7wtqkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzb7wtqkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:v-kontakte-logo" {...props}></Icon>
