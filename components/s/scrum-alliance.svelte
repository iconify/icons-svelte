<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxa8a0btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxa8a0btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:scrum-alliance" {...props}></Icon>
