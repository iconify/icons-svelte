<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4v084nuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4v084nuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:skip-forward-outline" {...props}></Icon>
