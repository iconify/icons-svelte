<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm7t8jb2j.css';
import '../../css/a/agsh3e2_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm7t8jb2j"/><path class="agsh3e2_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wan" {...props}></Icon>
