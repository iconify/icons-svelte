<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qovs41bxq.css';
import '../../css/b/bmffqxcpw.css';
import '../../css/p/p-xw0w-5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qovs41bxq"/><path class="bmffqxcpw"/><path class="p-xw0w-5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wand-20" {...props}></Icon>
