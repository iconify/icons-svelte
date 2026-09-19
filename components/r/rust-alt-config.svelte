<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnh7u9f3r.css';
import '../../css/v/v_9terb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gnh7u9f3r"/><path class="v_9terb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:rust-alt-config" {...props}></Icon>
