<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt56d1y2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gt56d1y2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-gum-inflammation-filled" {...props}></Icon>
