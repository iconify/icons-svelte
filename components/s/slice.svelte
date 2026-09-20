<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohx3qob0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohx3qob0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:slice" {...props}></Icon>
