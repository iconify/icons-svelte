<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buc8bcb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-8,"top":-1};
const content = `<path class="buc8bcb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:torch-f" {...props}></Icon>
