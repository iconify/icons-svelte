<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuqu0cbld.css';
import '../../css/k/karvylbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuqu0cbld"/><path class="karvylbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:users-fill" {...props}></Icon>
