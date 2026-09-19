<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6e4blykc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v6e4blykc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:treadmill" {...props}></Icon>
