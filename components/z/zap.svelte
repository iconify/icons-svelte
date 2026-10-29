<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhm81xbjd.css';
import '../../css/h/hqfaq1dih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhm81xbjd"/><path class="hqfaq1dih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:zap" {...props}></Icon>
