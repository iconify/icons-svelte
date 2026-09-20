<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd8qb6rig.css';
import '../../css/t/tvj-li2ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd8qb6rig"/><path class="tvj-li2ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:vote-yeah-solid" {...props}></Icon>
