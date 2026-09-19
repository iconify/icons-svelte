<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4ut14voh.css';
import '../../css/j/jinu42run.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="h4ut14voh"/><path class="jinu42run"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-codepen-outline" {...props}></Icon>
