<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_62dabzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="k_62dabzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:whistle" {...props}></Icon>
