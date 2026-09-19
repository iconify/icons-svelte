<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z35tf_spx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z35tf_spx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sailboat-one" {...props}></Icon>
