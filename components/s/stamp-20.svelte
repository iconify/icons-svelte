<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6jb10bks.css';
import '../../css/k/kp1vk88ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q6jb10bks"/><path class="kp1vk88ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stamp-20" {...props}></Icon>
