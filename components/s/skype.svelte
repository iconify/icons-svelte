<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy_vm35sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gy_vm35sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:skype" {...props}></Icon>
