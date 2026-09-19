<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2mf5ebrq.css';
import '../../css/o/o_3md2c4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g2mf5ebrq"/><path class="o_3md2c4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:scilla" {...props}></Icon>
