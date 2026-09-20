<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je16lsbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je16lsbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:travis-ci" {...props}></Icon>
