<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp7lwtiqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zp7lwtiqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:stethoscope" {...props}></Icon>
