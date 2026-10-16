<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siwllabzz.css';
import '../../css/n/no61rhzxq.css';
import '../../css/g/gnzoq5b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="siwllabzz"/><path class="no61rhzxq"/><path class="gnzoq5b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spray-can-20-bold" {...props}></Icon>
