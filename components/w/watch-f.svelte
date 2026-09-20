<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzf4xnbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-1};
const content = `<path class="gzf4xnbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:watch-f" {...props}></Icon>
