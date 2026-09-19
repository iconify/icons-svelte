<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8j_bxbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8j_bxbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:selection" {...props}></Icon>
