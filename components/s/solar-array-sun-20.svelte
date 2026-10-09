<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1l6u8egw.css';
import '../../css/w/w96urvnks.css';
import '../../css/m/m-4vi5jcl.css';
import '../../css/k/kj6hglb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b1l6u8egw"/><path class="w96urvnks"/><path class="m-4vi5jcl"/><path class="kj6hglb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-array-sun-20" {...props}></Icon>
