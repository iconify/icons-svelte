<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd_695mew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kd_695mew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:scales-unbalanced" {...props}></Icon>
