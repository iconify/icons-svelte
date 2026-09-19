<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3un--ltu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3un--ltu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:save" {...props}></Icon>
