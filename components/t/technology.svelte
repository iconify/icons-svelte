<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgujrohyl.css';
import '../../css/b/b07penbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgujrohyl"/><path class="b07penbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:technology" {...props}></Icon>
