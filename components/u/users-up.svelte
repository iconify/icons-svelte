<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf4hgk1ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf4hgk1ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:users-up" {...props}></Icon>
