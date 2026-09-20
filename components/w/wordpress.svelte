<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj9wosb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj9wosb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wordpress" {...props}></Icon>
