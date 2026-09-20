<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw6ui7bhy.css';
import '../../css/s/syf0cfsom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="kw6ui7bhy"/><path class="syf0cfsom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:wordpress-simple" {...props}></Icon>
