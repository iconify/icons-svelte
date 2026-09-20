<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvb5if0vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvb5if0vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield-plus-filled" {...props}></Icon>
