<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h30s1pbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h30s1pbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:scrum-alliance" {...props}></Icon>
