<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk3u-db7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk3u-db7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:settings-x" {...props}></Icon>
