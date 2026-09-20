<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e42jsrbou.css';
import '../../css/n/nv2zrkb9a.css';
import '../../css/v/v3ao27dlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e42jsrbou"/><path class="nv2zrkb9a"/><path class="v3ao27dlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-blessed" {...props}></Icon>
