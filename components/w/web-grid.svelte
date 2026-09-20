<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj8o_xb5j.css';
import '../../css/m/mqstf9bxa.css';
import '../../css/x/xlvhy0vyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj8o_xb5j"/><path class="mqstf9bxa"/><path class="xlvhy0vyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:web-grid" {...props}></Icon>
