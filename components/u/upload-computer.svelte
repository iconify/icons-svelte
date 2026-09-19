<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eud7tjtke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eud7tjtke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:upload-computer" {...props}></Icon>
