<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmstlq_8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmstlq_8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:svg-file" {...props}></Icon>
