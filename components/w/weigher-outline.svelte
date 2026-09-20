<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn-0ytboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gn-0ytboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:weigher-outline" {...props}></Icon>
