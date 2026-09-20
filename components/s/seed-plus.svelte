<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eli8gablv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eli8gablv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seed-plus" {...props}></Icon>
