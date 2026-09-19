<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bywkocsmn.css';
import '../../css/t/tvvbqnhhg.css';
import '../../css/c/credxixyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bywkocsmn"/><circle class="tvvbqnhhg"/><path class="credxixyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-destination" {...props}></Icon>
