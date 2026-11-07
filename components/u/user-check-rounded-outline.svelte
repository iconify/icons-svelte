<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6d250bwp.css';
import '../../css/c/cf8jt1bey.css';
import '../../css/j/jt-vrxbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6d250bwp"/><path class="cf8jt1bey"/><path clip-rule="evenodd" class="jt-vrxbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-check-rounded-outline" {...props}></Icon>
