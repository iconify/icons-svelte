<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fitiderwm.css';
import '../../css/g/g8_by6k8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fitiderwm"/><path class="g8_by6k8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:sensitive-duotone" {...props}></Icon>
