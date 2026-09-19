<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsu-6cu0h.css';
import '../../css/a/ao3chnvww.css';
import '../../css/h/hgxfgonkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tsu-6cu0h"/><path class="ao3chnvww"/><path class="hgxfgonkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vagrant-wordmark" {...props}></Icon>
