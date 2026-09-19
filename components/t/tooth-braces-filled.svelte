<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd9-2o1_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fd9-2o1_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-braces-filled" {...props}></Icon>
