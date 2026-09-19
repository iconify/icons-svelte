<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpjn_4b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kpjn_4b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:vector-circle" {...props}></Icon>
