<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fedk4wb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fedk4wb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:waist-circumference-outline" {...props}></Icon>
