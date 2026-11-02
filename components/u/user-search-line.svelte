<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs_uqt8kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs_uqt8kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-search-line" {...props}></Icon>
