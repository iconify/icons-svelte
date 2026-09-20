<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkr1zibwd.css';
import '../../css/p/pincndczi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkr1zibwd"/><path class="pincndczi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:trash-can-duotone" {...props}></Icon>
