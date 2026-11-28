<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju6kvy1jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju6kvy1jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-power-solid" {...props}></Icon>
