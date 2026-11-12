<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdaxo33rn.css';
import '../../css/s/s1wngpzxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bdaxo33rn"/><path class="s1wngpzxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yundera-dark" {...props}></Icon>
