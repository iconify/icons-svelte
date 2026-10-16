<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpxr-ob7u.css';
import '../../css/v/v7-g3_bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wpxr-ob7u"/><path class="v7-g3_bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:winch-48-bold" {...props}></Icon>
