<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubssz1bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ubssz1bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:triangle-20-solid" {...props}></Icon>
