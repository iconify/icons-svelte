<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_kwlg0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v3_kwlg0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:thermometer-one" {...props}></Icon>
