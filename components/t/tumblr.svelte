<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg3a7lbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg3a7lbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:tumblr" {...props}></Icon>
