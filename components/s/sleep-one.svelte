<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofrod_8io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ofrod_8io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sleep-one" {...props}></Icon>
