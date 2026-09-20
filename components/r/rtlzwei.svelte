<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx7tgkbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx7tgkbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rtlzwei" {...props}></Icon>
