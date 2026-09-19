<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb_xxc1-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":255,"height":754};
const content = `<path class="nb_xxc1-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:t" {...props}></Icon>
