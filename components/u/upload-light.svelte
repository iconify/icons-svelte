<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxh0f2bbu.css';
import '../../css/r/rqmkcsbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oxh0f2bbu"/><path class="rqmkcsbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:upload-light" {...props}></Icon>
