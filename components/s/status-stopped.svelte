<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnc9k-r_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="gnc9k-r_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:status-stopped" {...props}></Icon>
