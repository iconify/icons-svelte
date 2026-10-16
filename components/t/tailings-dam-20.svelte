<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gugafwbru.css';
import '../../css/p/pkpr5tboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gugafwbru"/><path class="pkpr5tboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tailings-dam-20" {...props}></Icon>
