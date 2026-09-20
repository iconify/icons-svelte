<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7ahsxa6g.css';
import '../../css/h/h-uptbcqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7ahsxa6g"/><path class="h-uptbcqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:signout-alt" {...props}></Icon>
