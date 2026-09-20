<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8v_ijbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f8v_ijbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:trending-content-solid" {...props}></Icon>
