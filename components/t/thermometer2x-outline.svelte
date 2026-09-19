<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1uqjgb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v1uqjgb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:thermometer2x-outline" {...props}></Icon>
