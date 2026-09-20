<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fio2bbb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fio2bbb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shrink-vertical-duotone" {...props}></Icon>
