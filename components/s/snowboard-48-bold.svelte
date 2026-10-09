<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-75ddbox.css';
import '../../css/g/gva8st1tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b-75ddbox"/><path class="gva8st1tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:snowboard-48-bold" {...props}></Icon>
