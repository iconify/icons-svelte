<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz4t6jbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zz4t6jbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:tablet-landscape-sharp" {...props}></Icon>
