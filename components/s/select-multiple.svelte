<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoy6vkbrs.css';
import '../../css/b/bpq3sbcle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoy6vkbrs"/><path class="bpq3sbcle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:select-multiple" {...props}></Icon>
