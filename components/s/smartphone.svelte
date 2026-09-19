<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw82yk4cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tw82yk4cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:smartphone" {...props}></Icon>
