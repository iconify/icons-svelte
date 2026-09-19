<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y837vvbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y837vvbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:user-edit-filled" {...props}></Icon>
