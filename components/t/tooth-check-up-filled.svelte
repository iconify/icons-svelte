<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt3ixjbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vt3ixjbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-check-up-filled" {...props}></Icon>
