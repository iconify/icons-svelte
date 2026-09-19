<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-ssoxb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-ssoxb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:users-group-outline" {...props}></Icon>
