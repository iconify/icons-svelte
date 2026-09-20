<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/banh9fb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="banh9fb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:train" {...props}></Icon>
