<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjxo99b9u.css';
import '../../css/d/dzyzyeb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjxo99b9u"/><path class="dzyzyeb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-group" {...props}></Icon>
