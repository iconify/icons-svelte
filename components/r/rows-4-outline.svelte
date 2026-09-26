<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr6o49biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fr6o49biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-4-outline" {...props}></Icon>
