<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1kj3t3ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1kj3t3ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:trigger" {...props}></Icon>
