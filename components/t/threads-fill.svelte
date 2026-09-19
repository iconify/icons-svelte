<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bro0eubko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bro0eubko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:threads-fill" {...props}></Icon>
