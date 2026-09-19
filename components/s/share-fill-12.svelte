<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfxlexb0t.css';
import '../../css/b/bn8wa4tsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sfxlexb0t"/><path class="bn8wa4tsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:share-fill-12" {...props}></Icon>
