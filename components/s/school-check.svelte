<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk9j21sug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk9j21sug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:school-check" {...props}></Icon>
