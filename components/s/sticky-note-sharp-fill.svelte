<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoyl7fb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aoyl7fb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sticky-note-sharp-fill" {...props}></Icon>
