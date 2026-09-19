<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7i8_6bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y7i8_6bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:stomach-outline" {...props}></Icon>
