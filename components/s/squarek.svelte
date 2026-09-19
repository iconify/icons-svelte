<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxnpk2b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="lxnpk2b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarek" {...props}></Icon>
